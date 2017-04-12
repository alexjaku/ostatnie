<?php

namespace WarsztatBundle\Entity;

use Doctrine\ORM\Mapping as ORM;

/**
 * Offer
 *
 * @ORM\Table(name="offer")
 * @ORM\Entity(repositoryClass="WarsztatBundle\Repository\OfferRepository")
 */
class Offer
{
    /**
     * @var int
     *
     * @ORM\Column(name="id", type="integer")
     * @ORM\Id
     * @ORM\GeneratedValue(strategy="AUTO")
     */
    private $id;

    /**
     * @var string
     *
     * @ORM\Column(name="price", type="decimal", precision=10, scale=2, nullable=true)
     */
    private $price;

    /**
     * @var int
     *
     * @ORM\Column(name="userTaskId", type="integer", nullable=true)
     */
    private $userTaskId;

    /**
     * @var int
     *
     * @ORM\Column(name="userOfferId", type="integer", nullable=true)
     */
    private $userOfferId;

    /**
     * @var int
     *
     * @ORM\Column(name="taskId", type="integer", nullable=true)
     */
    private $taskId;


    /**
     * Get id
     *
     * @return integer 
     */
    public function getId()
    {
        return $this->id;
    }

    /**
     * Set price
     *
     * @param string $price
     * @return Offer
     */
    public function setPrice($price)
    {
        $this->price = $price;

        return $this;
    }

    /**
     * Get price
     *
     * @return string 
     */
    public function getPrice()
    {
        return $this->price;
    }

    /**
     * Set userTaskId
     *
     * @param integer $userTaskId
     * @return Offer
     */
    public function setUserTaskId($userTaskId)
    {
        $this->userTaskId = $userTaskId;

        return $this;
    }

    /**
     * Get userTaskId
     *
     * @return integer 
     */
    public function getUserTaskId()
    {
        return $this->userTaskId;
    }

    /**
     * Set userOfferId
     *
     * @param integer $userOfferId
     * @return Offer
     */
    public function setUserOfferId($userOfferId)
    {
        $this->userOfferId = $userOfferId;

        return $this;
    }

    /**
     * Get userOfferId
     *
     * @return integer 
     */
    public function getUserOfferId()
    {
        return $this->userOfferId;
    }

    /**
     * Set taskId
     *
     * @param integer $taskId
     * @return Offer
     */
    public function setTaskId($taskId)
    {
        $this->taskId = $taskId;

        return $this;
    }

    /**
     * Get taskId
     *
     * @return integer 
     */
    public function getTaskId()
    {
        return $this->taskId;
    }
}
